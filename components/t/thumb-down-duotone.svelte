<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0kliu38q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0kliu38q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:thumb-down-duotone" {...props}></Icon>
