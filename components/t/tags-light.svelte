<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8m_hmjin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k8m_hmjin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:tags-light" {...props}></Icon>
