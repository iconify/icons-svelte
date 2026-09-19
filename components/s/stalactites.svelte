<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo6_qdb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo6_qdb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stalactites" {...props}></Icon>
