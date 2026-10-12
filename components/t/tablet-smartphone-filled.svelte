<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1se8tbgo.css';
import '../../css/q/qje49sx-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1se8tbgo"/><path class="qje49sx-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tablet-smartphone-filled" {...props}></Icon>
