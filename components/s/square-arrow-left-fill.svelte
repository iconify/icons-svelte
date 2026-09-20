<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8667_4va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8667_4va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-left-fill" {...props}></Icon>
