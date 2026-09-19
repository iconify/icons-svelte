<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqr3tj4qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr3tj4qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-square-light" {...props}></Icon>
