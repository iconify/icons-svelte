<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg76_7bbe.css';
import '../../css/m/m0b8pab-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer eg76_7bbe"/><path class="duoicon-secondary-layer m0b8pab-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:toggle" {...props}></Icon>
