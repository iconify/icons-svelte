<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmtb2gbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tmtb2gbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:top-data-sets" {...props}></Icon>
