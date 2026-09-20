<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnrcdpand.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnrcdpand"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:vuejs" {...props}></Icon>
