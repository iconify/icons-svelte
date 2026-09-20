<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns7uf-p8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns7uf-p8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:thumbs-up" {...props}></Icon>
