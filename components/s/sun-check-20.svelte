<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8nww4mnw.css';
import '../../css/m/mg--uz6gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8nww4mnw"/><path class="mg--uz6gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-check-20" {...props}></Icon>
