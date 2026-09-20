<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb9_o8s9v.css';
import '../../css/d/dkpju-4cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cb9_o8s9v"/><path class="dkpju-4cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sweats-fill" {...props}></Icon>
