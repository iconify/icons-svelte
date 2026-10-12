<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui5tlxbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui5tlxbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-heading-five" {...props}></Icon>
