<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo7efloty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":503,"height":735};
const content = `<path class="mo7efloty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:z-upper-case" {...props}></Icon>
