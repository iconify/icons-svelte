<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjo5wgb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjo5wgb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-align-right" {...props}></Icon>
