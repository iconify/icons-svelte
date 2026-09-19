<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeij0ebxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aeij0ebxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:skip-back" {...props}></Icon>
