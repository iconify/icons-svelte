<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl2egfq-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl2egfq-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:taxi" {...props}></Icon>
