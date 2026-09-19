<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4-7y7bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4-7y7bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shopping-bag-fill" {...props}></Icon>
