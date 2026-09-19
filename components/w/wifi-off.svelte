<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cya1rgi2m.css';
import '../../css/s/s7ta3byys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="cya1rgi2m"/><path class="s7ta3byys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wifi-off" {...props}></Icon>
