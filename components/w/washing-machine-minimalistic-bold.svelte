<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5e6tzbau.css';
import '../../css/l/lg5xwxuqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5e6tzbau"/><path clip-rule="evenodd" class="lg5xwxuqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:washing-machine-minimalistic-bold" {...props}></Icon>
