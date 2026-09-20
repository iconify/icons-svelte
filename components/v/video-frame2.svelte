<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_sj-dt-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_sj-dt-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-frame2" {...props}></Icon>
