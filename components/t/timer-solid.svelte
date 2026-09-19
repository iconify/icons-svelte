<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqt1wop1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqt1wop1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:timer-solid" {...props}></Icon>
