<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkonw3bdh.css';
import '../../css/s/skxq2dbrt.css';
import '../../css/g/g6shut3wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkonw3bdh"/><path class="skxq2dbrt"/><path class="g6shut3wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sanitizer-alt" {...props}></Icon>
