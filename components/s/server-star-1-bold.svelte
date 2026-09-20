<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojjc2sbvn.css';
import '../../css/o/oh7nkob3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojjc2sbvn"/><path class="oh7nkob3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:server-star-1-bold" {...props}></Icon>
