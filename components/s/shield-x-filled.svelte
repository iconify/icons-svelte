<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajqb8bb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajqb8bb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-x-filled" {...props}></Icon>
