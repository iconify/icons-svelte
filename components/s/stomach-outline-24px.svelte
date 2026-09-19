<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf2dofk5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf2dofk5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stomach-outline-24px" {...props}></Icon>
