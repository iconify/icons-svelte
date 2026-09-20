<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf4a-abip.css';
import '../../css/b/b45rmqb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4a-abip"/><path class="b45rmqb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:user-plus" {...props}></Icon>
