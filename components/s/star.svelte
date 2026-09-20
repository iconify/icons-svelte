<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvca--esl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvca--esl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:star" {...props}></Icon>
