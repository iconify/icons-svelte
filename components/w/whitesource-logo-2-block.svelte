<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoe_q5b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zoe_q5b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:whitesource-logo-2-block" {...props}></Icon>
