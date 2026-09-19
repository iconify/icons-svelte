<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuw_msbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuw_msbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-simple-fill" {...props}></Icon>
