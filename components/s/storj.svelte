<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ruqhyhp.css';
import '../../css/p/p95k6o2lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ruqhyhp"/><path clip-rule="evenodd" class="p95k6o2lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:storj" {...props}></Icon>
