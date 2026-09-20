<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv4eu2o7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv4eu2o7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unfold-more-fill" {...props}></Icon>
