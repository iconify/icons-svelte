<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7xgeab2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7xgeab2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:trending-up" {...props}></Icon>
