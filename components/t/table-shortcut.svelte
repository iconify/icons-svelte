<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz5dirmwx.css';
import '../../css/s/s-cmdjj4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pz5dirmwx"/><path class="s-cmdjj4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:table-shortcut" {...props}></Icon>
