<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u68y6wqkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u68y6wqkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vodafone-logo-block" {...props}></Icon>
