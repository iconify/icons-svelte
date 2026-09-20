<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocxtnncco.css';
import '../../css/f/fb07yqbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocxtnncco"/><path class="fb07yqbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:tag" {...props}></Icon>
