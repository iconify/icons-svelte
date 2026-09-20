<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj0391bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj0391bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ship" {...props}></Icon>
