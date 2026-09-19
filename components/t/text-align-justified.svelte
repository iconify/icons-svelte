<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvmey9bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvmey9bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:text-align-justified" {...props}></Icon>
