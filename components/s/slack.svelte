<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmhysybif.css';
import '../../css/s/sbtxsib7i.css';
import '../../css/e/erzbhu1-s.css';
import '../../css/b/bqg7jocgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhysybif"/><path class="sbtxsib7i"/><path class="erzbhu1-s"/><path class="bqg7jocgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:slack" {...props}></Icon>
