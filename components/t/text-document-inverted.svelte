<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg-_peskw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vg-_peskw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:text-document-inverted" {...props}></Icon>
