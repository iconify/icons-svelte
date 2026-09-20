<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7xadxb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7xadxb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wave-24" {...props}></Icon>
