<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnpbp5f4y.css';
import '../../css/g/gk7wsqrvw.css';
import '../../css/r/rzr3q0bfp.css';
import '../../css/h/hu6ejdbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="gnpbp5f4y"/><path class="gk7wsqrvw"/><path class="rzr3q0bfp"/><path class="hu6ejdbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:workload-identity-pool" {...props}></Icon>
