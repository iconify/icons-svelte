<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnh1pz82n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnh1pz82n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:settings-cog" {...props}></Icon>
