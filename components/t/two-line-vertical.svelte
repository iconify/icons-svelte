<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwmxn8bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmxn8bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:two-line-vertical" {...props}></Icon>
