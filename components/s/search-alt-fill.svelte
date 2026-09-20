<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibq2rdfwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibq2rdfwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:search-alt-fill" {...props}></Icon>
