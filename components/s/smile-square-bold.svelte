<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ywt_bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6ywt_bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smile-square-bold" {...props}></Icon>
