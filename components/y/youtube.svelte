<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgpquq.css';
import '../../css/b/bxtoun.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d--8d_6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgpquq"/><path class="bxtoun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:youtube" {...props}></Icon>
