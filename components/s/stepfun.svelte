<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqe5b6w_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqe5b6w_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stepfun" {...props}></Icon>
