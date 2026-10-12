<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6567db_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6567db_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vector-square-filled" {...props}></Icon>
