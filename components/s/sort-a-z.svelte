<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8r-wtbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8r-wtbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sort-a-z" {...props}></Icon>
