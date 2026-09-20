<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owkn8rban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owkn8rban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-merge" {...props}></Icon>
