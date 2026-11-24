<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv9me8bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv9me8bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:step-forward-solid" {...props}></Icon>
