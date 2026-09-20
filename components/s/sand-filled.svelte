<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6zcob98t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o6zcob98t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sand-filled" {...props}></Icon>
