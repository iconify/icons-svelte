<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puiv42zjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puiv42zjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shinto-shrine" {...props}></Icon>
