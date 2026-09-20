<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgavx_zmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgavx_zmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:share-link-remix" {...props}></Icon>
