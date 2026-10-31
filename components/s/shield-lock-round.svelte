<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwxx7l1ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwxx7l1ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-lock-round" {...props}></Icon>
