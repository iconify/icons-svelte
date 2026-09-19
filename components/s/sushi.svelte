<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_7bycxnx.css';
import '../../css/u/uqzyn-kgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_7bycxnx"/><path class="uqzyn-kgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sushi" {...props}></Icon>
