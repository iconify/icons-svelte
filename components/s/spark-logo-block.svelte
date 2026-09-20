<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfq14obvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfq14obvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:spark-logo-block" {...props}></Icon>
