<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id4air0sa.css';
import '../../css/z/z6k-h7b9c.css';
import '../../css/h/h8c2zibww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="id4air0sa"/><path class="z6k-h7b9c"/><path class="h8c2zibww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-path-outline" {...props}></Icon>
