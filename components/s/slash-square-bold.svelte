<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obu2jwbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obu2jwbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slash-square-bold" {...props}></Icon>
