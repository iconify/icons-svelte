<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpg09-1kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpg09-1kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transaction-yuan" {...props}></Icon>
