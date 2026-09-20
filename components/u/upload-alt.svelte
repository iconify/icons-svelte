<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh93e5uni.css';
import '../../css/c/c22lcubke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh93e5uni"/><path class="c22lcubke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:upload-alt" {...props}></Icon>
