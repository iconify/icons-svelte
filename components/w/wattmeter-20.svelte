<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrs6n7bep.css';
import '../../css/w/w2gzq9yrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nrs6n7bep"/><path class="w2gzq9yrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wattmeter-20" {...props}></Icon>
