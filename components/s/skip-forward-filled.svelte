<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf-hs-btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf-hs-btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:skip-forward-filled" {...props}></Icon>
