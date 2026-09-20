<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axw7n_bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axw7n_bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:table-plus" {...props}></Icon>
