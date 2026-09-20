<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpmf6gm_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpmf6gm_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shop2" {...props}></Icon>
