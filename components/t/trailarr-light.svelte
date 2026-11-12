<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqyns6bnn.css';
import '../../css/n/nt61mgt6m.css';
import '../../css/o/om4uewb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqyns6bnn"/><path class="nt61mgt6m"/><path class="om4uewb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trailarr-light" {...props}></Icon>
