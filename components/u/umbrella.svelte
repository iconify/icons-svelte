<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw6k_dayf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":628,"height":694};
const content = `<path class="fw6k_dayf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:umbrella" {...props}></Icon>
