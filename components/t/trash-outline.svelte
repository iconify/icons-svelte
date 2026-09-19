<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyhh9xlgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhh9xlgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:trash-outline" {...props}></Icon>
