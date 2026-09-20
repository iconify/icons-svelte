<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq56j2bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq56j2bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tornado" {...props}></Icon>
