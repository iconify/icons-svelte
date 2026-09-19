<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4fpbcob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf4fpbcob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-line-height" {...props}></Icon>
