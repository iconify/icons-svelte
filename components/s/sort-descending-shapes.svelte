<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eao8dbouc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eao8dbouc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-descending-shapes" {...props}></Icon>
