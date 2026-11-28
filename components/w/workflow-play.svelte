<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1w820bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1w820bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:workflow-play" {...props}></Icon>
