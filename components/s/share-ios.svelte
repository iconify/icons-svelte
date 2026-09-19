<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om-kxybtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="om-kxybtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:share-ios" {...props}></Icon>
