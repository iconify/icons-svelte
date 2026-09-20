<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkj9tpb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkj9tpb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xki" {...props}></Icon>
