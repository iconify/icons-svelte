<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42iuqbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k42iuqbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-outline" {...props}></Icon>
