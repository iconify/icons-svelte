<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poe7_bcmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poe7_bcmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:share-alt" {...props}></Icon>
