<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_1n2bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md_1n2bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:yaml" {...props}></Icon>
