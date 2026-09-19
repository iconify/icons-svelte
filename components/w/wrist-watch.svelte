<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3pqhgbsx.css';
import '../../css/o/obc0bdcuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3pqhgbsx"/><path class="obc0bdcuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch" {...props}></Icon>
