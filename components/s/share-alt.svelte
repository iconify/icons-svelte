<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u-fwcor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8u-fwcor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:share-alt" {...props}></Icon>
