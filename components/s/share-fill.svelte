<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exm28zjag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exm28zjag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:share-fill" {...props}></Icon>
