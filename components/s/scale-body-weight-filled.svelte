<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww20d8b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww20d8b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scale-body-weight-filled" {...props}></Icon>
