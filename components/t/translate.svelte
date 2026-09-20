<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr0g9xbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fr0g9xbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:translate" {...props}></Icon>
