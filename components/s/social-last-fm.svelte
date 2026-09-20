<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_o0lhbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_o0lhbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-last-fm" {...props}></Icon>
