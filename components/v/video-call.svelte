<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu4speh-f.css';
import '../../css/w/w89bx5biq.css';
import '../../css/l/l5bbw4b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu4speh-f wm-k"/><path class="w89bx5biq wm-a"/><path class="l5bbw4b8q wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:video-call" {...props}></Icon>
