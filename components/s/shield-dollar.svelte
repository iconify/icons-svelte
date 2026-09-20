<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsi7ipshf.css';
import '../../css/p/p3hf5o7_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="fsi7ipshf"/><path clip-rule="evenodd" class="p3hf5o7_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shield-dollar" {...props}></Icon>
