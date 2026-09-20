<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_d0yw8xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_d0yw8xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-select-mode-16" {...props}></Icon>
