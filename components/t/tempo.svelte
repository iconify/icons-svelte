<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq_jegu-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq_jegu-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tempo" {...props}></Icon>
