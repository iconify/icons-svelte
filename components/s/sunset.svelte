<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o91sm0_iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="o91sm0_iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sunset" {...props}></Icon>
