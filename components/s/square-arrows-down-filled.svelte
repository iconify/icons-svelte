<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujl_nsbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ujl_nsbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrows-down-filled" {...props}></Icon>
