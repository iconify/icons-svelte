<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqimr2thp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqimr2thp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-dollar" {...props}></Icon>
