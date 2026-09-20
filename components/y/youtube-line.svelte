<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj_edtbco.css';
import '../../css/n/n3kf-o-ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj_edtbco"/><path class="n3kf-o-ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:youtube-line" {...props}></Icon>
