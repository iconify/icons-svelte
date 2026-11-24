<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t01_zdb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t01_zdb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rugby-ball-filled" {...props}></Icon>
