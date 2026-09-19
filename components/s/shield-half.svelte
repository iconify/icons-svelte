<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b00879b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b00879b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shield-half" {...props}></Icon>
