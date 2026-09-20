<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eypp7rb0r.css';
import '../../css/a/a224fdcsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="eypp7rb0r"/><path clip-rule="evenodd" class="a224fdcsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:weight-machine-1" {...props}></Icon>
