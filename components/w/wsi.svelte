<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i05fakbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i05fakbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wsi" {...props}></Icon>
