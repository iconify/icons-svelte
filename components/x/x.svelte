<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scw5hpb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scw5hpb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:x" {...props}></Icon>
