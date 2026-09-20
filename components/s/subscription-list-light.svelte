<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kawm64b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kawm64b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:subscription-list-light" {...props}></Icon>
