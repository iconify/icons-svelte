<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr8ohcc6r.css';
import '../../css/g/gsazuob2v.css';
import '../../css/y/ytm2n1ogb.css';
import '../../css/s/snk62fbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jr8ohcc6r"/><path class="gsazuob2v"/><path class="ytm2n1ogb"/><path class="snk62fbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:singapore" {...props}></Icon>
