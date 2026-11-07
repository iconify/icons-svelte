<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/out_eubyp.css';
import '../../css/w/wh1vxda8i.css';
import '../../css/u/u4zxjwj4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="out_eubyp"/><path class="wh1vxda8i"/><path class="u4zxjwj4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:xxx-bold" {...props}></Icon>
