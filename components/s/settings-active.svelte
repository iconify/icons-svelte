<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fom46j_ot.css';
import '../../css/g/go0tywt9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fom46j_ot"/><path clip-rule="evenodd" class="go0tywt9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:settings-active" {...props}></Icon>
