<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8g612boj.css';
import '../../css/q/qwz7habez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8g612boj st0"/><path class="qwz7habez st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:waffle-filled" {...props}></Icon>
