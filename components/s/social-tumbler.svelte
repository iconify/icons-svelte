<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvsefhbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvsefhbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-tumbler" {...props}></Icon>
