<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nctuibqln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nctuibqln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-out-24" {...props}></Icon>
