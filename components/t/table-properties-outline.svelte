<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmfj0ubqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmfj0ubqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:table-properties-outline" {...props}></Icon>
