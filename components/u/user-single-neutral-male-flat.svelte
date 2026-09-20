<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfh940b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfh940b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:user-single-neutral-male-flat" {...props}></Icon>
