<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaazzmbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaazzmbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:thumbs-up-fill" {...props}></Icon>
