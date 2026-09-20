<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3mlc2byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o3mlc2byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:ruler" {...props}></Icon>
