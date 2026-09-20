<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxumftbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bxumftbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-insert-column-right" {...props}></Icon>
