<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvdr71a1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvdr71a1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-check" {...props}></Icon>
